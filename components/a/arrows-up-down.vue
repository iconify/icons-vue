<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycj6sccto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycj6sccto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:arrows-up-down" /></template>
