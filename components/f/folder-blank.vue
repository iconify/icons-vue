<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7e3msbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="c7e3msbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:folder-blank" /></template>
