<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llfhb1b4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":472};
const content = `<path class="llfhb1b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:cake" /></template>
