<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsca1gb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wsca1gb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:badge-cc-fill" /></template>
