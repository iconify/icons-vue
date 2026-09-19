<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu5i0ibdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":456};
const content = `<path class="pu5i0ibdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:lock-open" /></template>
