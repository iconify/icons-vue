<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbmn4jfpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kbmn4jfpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-person-fill" /></template>
