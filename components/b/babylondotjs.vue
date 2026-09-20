<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_g3u5eqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_g3u5eqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:babylondotjs" /></template>
