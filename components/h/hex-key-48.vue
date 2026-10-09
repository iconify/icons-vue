<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt8_zhj7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xt8_zhj7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hex-key-48" /></template>
