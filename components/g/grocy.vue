<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qai1goviu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qai1goviu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:grocy" /></template>
