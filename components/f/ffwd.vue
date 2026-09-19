<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8h5-2k2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="j8h5-2k2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:ffwd" /></template>
