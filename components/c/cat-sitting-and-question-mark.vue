<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg8vo_0ux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jg8vo_0ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cat-sitting-and-question-mark" /></template>
