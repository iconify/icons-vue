<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg22kut3v.css';
import '../../css/o/ojajqfjbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tg22kut3v"/><path class="ojajqfjbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:disconnector-48" /></template>
