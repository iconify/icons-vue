<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbqtqn7md.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xbqtqn7md"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:assignee" /></template>
