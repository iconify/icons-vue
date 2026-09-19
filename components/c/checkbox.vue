<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6qqvlb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":700,"height":677};
const content = `<path class="k6qqvlb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:checkbox" /></template>
