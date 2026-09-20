<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqvpc5b1j.css';
import '../../css/o/osrarucge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dqvpc5b1j"/><path class="osrarucge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:bookmark-list-rtl" /></template>
