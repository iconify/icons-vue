<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7fn5abah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a7fn5abah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevron-down-48-bold" /></template>
