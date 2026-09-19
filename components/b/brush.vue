<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iea4lyb4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iea4lyb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:brush" /></template>
