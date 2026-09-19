<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahe28pluw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ahe28pluw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:gitlab" /></template>
