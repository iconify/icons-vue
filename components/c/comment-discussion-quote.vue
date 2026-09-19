<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l562sp3ng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l562sp3ng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:comment-discussion-quote" /></template>
