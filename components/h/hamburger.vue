<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4os67b3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r4os67b3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:hamburger" /></template>
