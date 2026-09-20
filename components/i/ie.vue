<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f__nc6b9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f__nc6b9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:ie" /></template>
