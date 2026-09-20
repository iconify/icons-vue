<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkbw6_bzt.css';
import '../../css/t/toym7nb7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="dkbw6_bzt"/><path class="toym7nb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:hook" /></template>
