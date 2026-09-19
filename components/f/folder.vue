<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1-v69juy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="l1-v69juy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:folder" /></template>
