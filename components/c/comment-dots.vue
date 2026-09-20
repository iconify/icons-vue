<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4zpm0b8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y4zpm0b8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:comment-dots" /></template>
