<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv4wv-b4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv4wv-b4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:500px" /></template>
