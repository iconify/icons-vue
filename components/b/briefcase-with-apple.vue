<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgquibciy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pgquibciy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:briefcase-with-apple" /></template>
