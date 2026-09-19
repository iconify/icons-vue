<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv9rlsbfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cv9rlsbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:hockeyapp" /></template>
