<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h05hsvrra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h05hsvrra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:flag-ltr" /></template>
