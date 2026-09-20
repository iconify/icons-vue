<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxtk6mbvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":55,"height":20};
const content = `<path clip-rule="evenodd" class="cxtk6mbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:aero-dark" /></template>
