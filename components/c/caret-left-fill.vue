<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il88ib7ab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="il88ib7ab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:caret-left-fill" /></template>
