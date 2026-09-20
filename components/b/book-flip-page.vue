<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9wtmta2j.css';
import '../../css/v/valpkebar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9wtmta2j"/><path class="valpkebar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:book-flip-page" /></template>
