<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omq3peb8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="omq3peb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:library-16" /></template>
