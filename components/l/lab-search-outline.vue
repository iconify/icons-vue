<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la_6nmkfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="la_6nmkfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:lab-search-outline" /></template>
