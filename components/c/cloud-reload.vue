<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvny9pook.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rvny9pook"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:cloud-reload" /></template>
