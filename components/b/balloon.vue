<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxh8aml4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bxh8aml4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:balloon" /></template>
