<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2mf_7bmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t2mf_7bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:list-ordered-48-bold" /></template>
