<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfje2gbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":274,"height":614};
const content = `<path class="jfje2gbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:hyphen" /></template>
