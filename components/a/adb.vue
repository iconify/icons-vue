<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vobn2vo6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":472};
const content = `<path class="vobn2vo6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:adb" /></template>
