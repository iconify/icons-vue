<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n26w-wbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n26w-wbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:chat-question-16" /></template>
