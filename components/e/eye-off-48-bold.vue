<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udbsvx9ze.css';
import '../../css/x/x6a75wd9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="udbsvx9ze"/><path class="x6a75wd9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:eye-off-48-bold" /></template>
