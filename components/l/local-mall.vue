<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea8c8v_1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":456};
const content = `<path class="ea8c8v_1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:local-mall" /></template>
