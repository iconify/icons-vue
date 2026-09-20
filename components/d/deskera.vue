<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovsu6pbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":458,"height":96};
const content = `<path class="ovsu6pbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:deskera" /></template>
