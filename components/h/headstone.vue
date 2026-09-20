<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-av3_bit.css';
import '../../css/r/r4_7jcbgs.css';
import '../../css/p/pc7f2vb6i.css';
import '../../css/o/oflaz1bix.css';
import '../../css/j/jcyo4yvaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="f-av3_bit"/><path class="r4_7jcbgs"/><path class="pc7f2vb6i"/><path class="oflaz1bix"/><path class="jcyo4yvaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:headstone" /></template>
