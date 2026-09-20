<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux02sgbdo.css';
import '../../css/a/aqhlej3kq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ux02sgbdo"/><path class="aqhlej3kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:health-ambulance-call" /></template>
