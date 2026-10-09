<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhkg43b8y.css';
import '../../css/b/bxrez7b8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nhkg43b8y"/><path class="bxrez7b8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ice-cream-20" /></template>
