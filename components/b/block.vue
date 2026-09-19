<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn5c3hbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="vn5c3hbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:block" /></template>
