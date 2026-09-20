<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhp6qvzak.css';
import '../../css/v/vo71evf5d.css';
import '../../css/j/jsyno-bnz.css';
import '../../css/e/e4zfowz9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="zhp6qvzak"/><path class="vo71evf5d"/><path class="jsyno-bnz"/><path class="e4zfowz9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:aquarius" /></template>
