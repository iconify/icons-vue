<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8g9pgb0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="d8g9pgb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:firstdraft" /></template>
