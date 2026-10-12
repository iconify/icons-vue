<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej-7496ya.css';
import '../../css/b/bbhbk04qj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ej-7496ya"/><path class="bbhbk04qj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hurricane-20" /></template>
