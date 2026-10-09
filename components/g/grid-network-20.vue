<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg1we5wmy.css';
import '../../css/w/wz_jv-b9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tg1we5wmy"/><path class="wz_jv-b9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grid-network-20" /></template>
