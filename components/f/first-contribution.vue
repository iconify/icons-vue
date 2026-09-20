<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axnb70bez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="axnb70bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:first-contribution" /></template>
