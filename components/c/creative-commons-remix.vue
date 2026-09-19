<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is22c2laj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="is22c2laj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:creative-commons-remix" /></template>
