<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9buk1bpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z9buk1bpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:delete" /></template>
