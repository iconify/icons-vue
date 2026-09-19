<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb4xue22f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="hb4xue22f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:account-calendar" /></template>
