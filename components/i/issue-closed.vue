<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6fytiy4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c6fytiy4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:issue-closed" /></template>
