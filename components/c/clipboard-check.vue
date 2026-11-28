<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arfc1ybtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arfc1ybtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:clipboard-check" /></template>
