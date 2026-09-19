<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd34iubbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zd34iubbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-down-right-square-fill" /></template>
