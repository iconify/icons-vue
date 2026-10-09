<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtkttskyz.css';
import '../../css/d/d1zhrdbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jtkttskyz"/><path class="d1zhrdbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flag-20-bold" /></template>
