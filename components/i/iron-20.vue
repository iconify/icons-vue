<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/liufp_b5i.css';
import '../../css/m/mgw7p7bzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="liufp_b5i"/><path class="mgw7p7bzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:iron-20" /></template>
