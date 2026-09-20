<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw7xbrb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rw7xbrb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ghostty-light" /></template>
