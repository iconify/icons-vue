<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k20casbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k20casbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:coin-minus" /></template>
