<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3djr2b_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r3djr2b_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:less-than-sign-circle-remix" /></template>
