<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgaqpcbiz.css';
import '../../css/l/lcaoj-wbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cgaqpcbiz"/><path class="lcaoj-wbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:folder" /></template>
