<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfyst0acy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hfyst0acy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:a-frame-tent" /></template>
