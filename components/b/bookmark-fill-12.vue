<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1-kqhbje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="d1-kqhbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bookmark-fill-12" /></template>
