<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe1kayn5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pe1kayn5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:convex-16" /></template>
