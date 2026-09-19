<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfar3hb-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":24};
const content = `<path class="hfar3hb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:magnet" /></template>
