<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngrxbbbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1792};
const content = `<path class="ngrxbbbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:calendar" /></template>
