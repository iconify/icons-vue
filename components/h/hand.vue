<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0y87j0bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o0y87j0bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:hand" /></template>
