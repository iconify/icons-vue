<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlmq6jb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nlmq6jb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:book-outline" /></template>
