<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1cpmz2ky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="l1cpmz2ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:gastroenterology" /></template>
