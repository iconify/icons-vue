<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os05-0bel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="os05-0bel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:file-excel" /></template>
