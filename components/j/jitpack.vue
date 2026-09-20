<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn-_cztfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zn-_cztfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:jitpack" /></template>
