<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-lfmccxy.css';
import '../../css/v/v2gr9gvbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i-lfmccxy"/><path class="v2gr9gvbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:comment-locked-16" /></template>
