<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6ncacbbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="i6ncacbbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:idea" /></template>
