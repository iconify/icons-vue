<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1v0u_7-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="s1v0u_7-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:lasso" /></template>
