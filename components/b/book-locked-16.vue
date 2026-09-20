<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-lfmccxy.css';
import '../../css/p/pn4efebvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i-lfmccxy"/><path class="pn4efebvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:book-locked-16" /></template>
