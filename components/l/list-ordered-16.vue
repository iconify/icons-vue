<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-kpfab6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v-kpfab6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:list-ordered-16" /></template>
