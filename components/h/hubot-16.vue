<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7l81db-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g7l81db-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:hubot-16" /></template>
