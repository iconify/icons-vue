<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqby3ib5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tqby3ib5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:ink-16" /></template>
