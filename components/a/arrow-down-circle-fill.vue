<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a61q8-b-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a61q8-b-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-down-circle-fill" /></template>
