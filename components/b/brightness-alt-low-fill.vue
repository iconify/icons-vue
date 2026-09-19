<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgfo6gb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bgfo6gb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:brightness-alt-low-fill" /></template>
