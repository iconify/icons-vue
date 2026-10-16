<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b30ptpbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b30ptpbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:check-check-20" /></template>
