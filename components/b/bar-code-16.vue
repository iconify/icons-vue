<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okr-h6u1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="okr-h6u1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:bar-code-16" /></template>
