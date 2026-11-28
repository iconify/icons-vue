<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaxykhbwe.css';
import '../../css/i/idwsbdxlg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary uaxykhbwe"/><path class="idwsbdxlg primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-big-down-duo" /></template>
