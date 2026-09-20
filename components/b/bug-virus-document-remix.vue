<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo2007t4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uo2007t4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bug-virus-document-remix" /></template>
