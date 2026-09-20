<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlem8ibph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tlem8ibph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:comment-o" /></template>
