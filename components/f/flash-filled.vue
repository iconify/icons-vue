<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp-pb1rgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wp-pb1rgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:flash-filled" /></template>
