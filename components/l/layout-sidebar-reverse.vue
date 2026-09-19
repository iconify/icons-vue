<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwwk4dnck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mwwk4dnck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:layout-sidebar-reverse" /></template>
