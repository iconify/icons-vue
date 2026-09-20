<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmwp9acui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dmwp9acui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:briefcase-with-question-mark" /></template>
