<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0kd4mg4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="v0kd4mg4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:dropbox-original" /></template>
