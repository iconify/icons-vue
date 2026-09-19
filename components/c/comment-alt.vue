<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jaj0pkbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1179,"height":1000};
const content = `<path class="jaj0pkbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:comment-alt" /></template>
