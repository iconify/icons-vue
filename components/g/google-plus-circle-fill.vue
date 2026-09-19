<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftf_zu7ol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ftf_zu7ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:google-plus-circle-fill" /></template>
