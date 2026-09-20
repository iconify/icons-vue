<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2be4_ncf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j2be4_ncf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:gitlab-fill-16" /></template>
