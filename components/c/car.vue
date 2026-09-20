<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igpwe4bxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="igpwe4bxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:car" /></template>
