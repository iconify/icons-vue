<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlv1ewbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zlv1ewbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:bookmark-x-mark-16-solid" /></template>
