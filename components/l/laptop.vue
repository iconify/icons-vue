<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqgpq5bla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tqgpq5bla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:laptop" /></template>
