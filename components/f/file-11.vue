<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgn3rcgnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mgn3rcgnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:file-11" /></template>
