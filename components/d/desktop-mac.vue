<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w323g6bsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":432};
const content = `<path class="w323g6bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:desktop-mac" /></template>
