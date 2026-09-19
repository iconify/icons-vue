<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plt-c4b5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="plt-c4b5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:account" /></template>
