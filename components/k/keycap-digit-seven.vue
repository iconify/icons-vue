<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixxthgb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ixxthgb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-digit-seven" /></template>
