<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8j8023wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x8j8023wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chat-right" /></template>
