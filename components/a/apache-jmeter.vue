<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtq4xgbbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtq4xgbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:apache-jmeter" /></template>
