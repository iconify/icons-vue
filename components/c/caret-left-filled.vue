<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z60422b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z60422b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:caret-left-filled" /></template>
