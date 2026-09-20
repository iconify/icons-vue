<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_yyoac7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i_yyoac7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:briefcase-with-greek-cross" /></template>
