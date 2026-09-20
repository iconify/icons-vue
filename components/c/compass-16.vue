<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brk4pcs8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="brk4pcs8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:compass-16" /></template>
