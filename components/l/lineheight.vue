<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjlroc2hg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1025};
const content = `<path class="vjlroc2hg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:lineheight" /></template>
