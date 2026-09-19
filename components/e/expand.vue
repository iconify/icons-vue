<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prgsuk5uv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="prgsuk5uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:expand" /></template>
