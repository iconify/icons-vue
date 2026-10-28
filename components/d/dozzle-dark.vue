<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnfy8t3pj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hnfy8t3pj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dozzle-dark" /></template>
