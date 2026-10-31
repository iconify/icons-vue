<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdjlbn8gp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zdjlbn8gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:check-square-16-solid" /></template>
