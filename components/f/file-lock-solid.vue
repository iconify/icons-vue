<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t37l2vbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t37l2vbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-lock-solid" /></template>
