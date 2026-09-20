<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrtz2jb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jrtz2jb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:flower-in-pot" /></template>
