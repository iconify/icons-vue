<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a75vaqbtg.css';
import '../../css/m/m-ex0ftgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a75vaqbtg"/><path class="m-ex0ftgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-export-filled" /></template>
