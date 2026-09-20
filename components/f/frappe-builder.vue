<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjc1npbxs.css';
import '../../css/s/saj3nzkks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qjc1npbxs"/><path class="saj3nzkks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-builder" /></template>
