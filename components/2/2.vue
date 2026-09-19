<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvvzgibti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":481,"height":754};
const content = `<path class="jvvzgibti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:2" /></template>
