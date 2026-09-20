<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyhljoa7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yyhljoa7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:castle-gate-with-battlements" /></template>
