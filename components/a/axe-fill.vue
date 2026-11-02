<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epm_5nbns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epm_5nbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:axe-fill" /></template>
