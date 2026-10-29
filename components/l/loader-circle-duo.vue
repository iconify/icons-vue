<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx2uz1-fm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx2uz1-fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:loader-circle-duo" /></template>
