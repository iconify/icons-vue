<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx0ku_hzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="lx0ku_hzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:bell" /></template>
