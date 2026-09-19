<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li6r0m7yr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":384};
const content = `<path class="li6r0m7yr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:close" /></template>
