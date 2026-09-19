<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2cy3dh3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j2cy3dh3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:emoji-neutral-fill" /></template>
