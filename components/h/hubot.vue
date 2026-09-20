<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcwvus9hb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="fcwvus9hb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:hubot" /></template>
