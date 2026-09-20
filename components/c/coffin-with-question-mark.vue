<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf_ta3b0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tf_ta3b0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:coffin-with-question-mark" /></template>
