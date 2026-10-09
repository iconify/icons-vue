<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do4ne9uns.css';
import '../../css/j/j89f_0dyx.css';
import '../../css/b/b6j267ddl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="do4ne9uns"/><path class="j89f_0dyx"/><path class="b6j267ddl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:git-branch-20-bold" /></template>
