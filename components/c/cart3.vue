<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o175cvbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o175cvbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cart3" /></template>
