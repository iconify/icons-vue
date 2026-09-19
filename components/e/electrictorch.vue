<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayzny56qx.css';
import '../../css/z/znznyqb7x.css';
import '../../css/o/ogxcobpnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ayzny56qx"/><path class="znznyqb7x"/><path class="ogxcobpnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:electrictorch" /></template>
