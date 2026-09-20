<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-o8tex9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d-o8tex9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:fish-under-fillet-knife" /></template>
