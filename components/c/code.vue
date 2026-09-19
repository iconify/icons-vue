<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kudgidczo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kudgidczo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:code" /></template>
