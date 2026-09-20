<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_gp79bkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_gp79bkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:file-plus-solid" /></template>
