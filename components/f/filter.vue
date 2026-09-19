<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1rfcp77z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s1rfcp77z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:filter" /></template>
