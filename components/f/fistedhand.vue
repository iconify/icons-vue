<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slzdijbqw.css';
import '../../css/p/pcxoghbnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="slzdijbqw"/><path class="pcxoghbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:fistedhand" /></template>
