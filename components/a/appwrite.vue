<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7bh2fp3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h7bh2fp3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:appwrite" /></template>
