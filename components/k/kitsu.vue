<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_m3rz_2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_m3rz_2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:kitsu" /></template>
