<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9w77bbrk.css';
import '../../css/z/zbefq9b9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="c9w77bbrk"/><path class="zbefq9b9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:apachespark-wordmark" /></template>
