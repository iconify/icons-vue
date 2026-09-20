<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8e7ms_4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="e8e7ms_4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:clock" /></template>
