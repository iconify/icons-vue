<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljj02nc5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ljj02nc5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:key-outline" /></template>
