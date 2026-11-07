<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6tsj1b8b.css';
import '../../css/u/uxo_8abdr.css';
import '../../css/e/ef63e0_qa.css';
import '../../css/w/wm3j448rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6tsj1b8b"/><path class="uxo_8abdr"/><path clip-rule="evenodd" class="ef63e0_qa"/><path class="wm3j448rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-pen-bold" /></template>
