<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsw1opb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsw1opb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:autoprefixer" /></template>
