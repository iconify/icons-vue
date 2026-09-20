<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edlu_rqaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edlu_rqaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-infor-fill" /></template>
