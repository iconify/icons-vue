<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/f7--fccjq.css';
import '../../css/z/z791spbav.css';
import '../../css/b/b9jcm8g0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="f7--fccjq"/><path class="z791spbav"/><path class="b9jcm8g0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:folder-open" /></template>
