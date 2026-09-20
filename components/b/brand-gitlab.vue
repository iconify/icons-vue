<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3l3ombav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3l3ombav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:brand-gitlab" /></template>
