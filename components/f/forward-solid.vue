<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aog-rgbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aog-rgbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:forward-solid" /></template>
