<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt3prvmif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vt3prvmif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:flag-rtl" /></template>
