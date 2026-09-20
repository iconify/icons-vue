<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsay_9bjz.css';
import '../../css/e/e56ncghit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xsay_9bjz"/><path class="e56ncghit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:git-pull-request-locked-16" /></template>
