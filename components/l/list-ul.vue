<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zetc7ib7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zetc7ib7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:list-ul" /></template>
