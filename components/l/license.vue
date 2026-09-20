<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb7dbebbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jb7dbebbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:license" /></template>
