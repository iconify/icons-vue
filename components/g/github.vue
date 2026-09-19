<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze_coeb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ze_coeb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:github" /></template>
