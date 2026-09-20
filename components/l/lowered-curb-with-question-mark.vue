<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1uxt3j4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d1uxt3j4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:lowered-curb-with-question-mark" /></template>
