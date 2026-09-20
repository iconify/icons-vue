<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nis8-pwmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="nis8-pwmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-file-folder-work-office-company-folder-supplies-file" /></template>
