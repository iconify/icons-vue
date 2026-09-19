<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db1by81sm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="db1by81sm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:flip-to-back" /></template>
