<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xss0pv79m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xss0pv79m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:boy" /></template>
