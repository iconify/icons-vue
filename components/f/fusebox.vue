<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlldztbnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":490,"height":512};
const content = `<path class="rlldztbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:fusebox" /></template>
