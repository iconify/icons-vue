<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gflrm4bxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gflrm4bxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:file-filled" /></template>
