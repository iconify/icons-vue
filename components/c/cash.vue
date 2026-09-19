<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqmgz0doi.css';
import '../../css/l/ld018kbkh.css';
import '../../css/f/f60e8jbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jqmgz0doi"/><path class="ld018kbkh"/><path class="f60e8jbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:cash" /></template>
