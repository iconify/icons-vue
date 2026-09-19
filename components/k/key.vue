<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr4438zbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yr4438zbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:key" /></template>
