<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx5n8lb2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zx5n8lb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:git-merge-sharp" /></template>
