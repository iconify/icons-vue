<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvpbq8bgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="hvpbq8bgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:local-printshop" /></template>
