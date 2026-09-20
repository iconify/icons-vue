<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2u2mlbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f2u2mlbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:hand-reaching-down-toward-rough-surface" /></template>
