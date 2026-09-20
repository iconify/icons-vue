<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzcftt5px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hzcftt5px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:fort-awesome" /></template>
