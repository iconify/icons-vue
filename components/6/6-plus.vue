<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2guqxb3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s2guqxb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:6-plus" /></template>
