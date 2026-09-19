<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aech68a0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aech68a0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-lg-fill-16" /></template>
