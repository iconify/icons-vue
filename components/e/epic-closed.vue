<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgk9pubpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lgk9pubpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:epic-closed" /></template>
