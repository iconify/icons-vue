<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apwqmbbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="apwqmbbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:bookmark-filled" /></template>
