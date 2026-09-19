<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne0xqbbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ne0xqbbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:collection-play-fill" /></template>
