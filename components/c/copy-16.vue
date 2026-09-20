<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3frkwgdc.css';
import '../../css/i/irv6a3b8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y3frkwgdc"/><path class="irv6a3b8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:copy-16" /></template>
