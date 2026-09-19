<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbgysbc5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jbgysbc5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:jiraalign-wordmark" /></template>
