<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x41tnzk-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x41tnzk-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:control-buttons-rewind" /></template>
