<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd-shmbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yd-shmbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:girl-cry" /></template>
