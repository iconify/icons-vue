<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st_hwob4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="st_hwob4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:flood" /></template>
