<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z89xl_g6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="z89xl_g6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:esports" /></template>
