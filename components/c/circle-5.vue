<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o45hv10in.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o45hv10in"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:circle-5" /></template>
