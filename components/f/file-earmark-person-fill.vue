<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0fztwm7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l0fztwm7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-earmark-person-fill" /></template>
