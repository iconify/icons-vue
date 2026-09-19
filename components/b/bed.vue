<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk52tmsyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dk52tmsyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:bed" /></template>
