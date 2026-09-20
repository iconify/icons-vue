<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2ru_1ven.css';
import '../../css/c/cpjb_5hdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2ru_1ven"/><path class="cpjb_5hdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:location-fill" /></template>
