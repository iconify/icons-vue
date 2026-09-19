<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2q10-yfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="k2q10-yfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-windows-filled" /></template>
