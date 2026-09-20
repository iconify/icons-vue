<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i25dcsbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i25dcsbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:information-o" /></template>
