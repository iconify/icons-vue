<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zevvw2r7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zevvw2r7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:2-square-fill" /></template>
