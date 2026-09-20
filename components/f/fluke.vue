<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf4dzib-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kf4dzib-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fluke" /></template>
