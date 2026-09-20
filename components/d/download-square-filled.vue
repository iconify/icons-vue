<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqq_6evck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sqq_6evck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:download-square-filled" /></template>
