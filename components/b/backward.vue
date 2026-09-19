<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0dc-4v8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="d0dc-4v8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:backward" /></template>
