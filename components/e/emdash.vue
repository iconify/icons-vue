<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik_ga42_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":643,"height":614};
const content = `<path class="ik_ga42_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:emdash" /></template>
