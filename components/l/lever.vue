<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okv-yobal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="okv-yobal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:lever" /></template>
