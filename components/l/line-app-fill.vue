<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okjh_kbci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okjh_kbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:line-app-fill" /></template>
