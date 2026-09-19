<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqwvi89jg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jqwvi89jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:box2-heart-fill" /></template>
