<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a26um7rpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="a26um7rpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:baby-crawling" /></template>
