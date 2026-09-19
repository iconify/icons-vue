<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl5wj4bmg.css';
import '../../css/j/jgmlxzbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl5wj4bmg"/><path class="jgmlxzbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-right-stroke-circle-half-filled" /></template>
