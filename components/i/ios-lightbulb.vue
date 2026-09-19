<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-sealbsy.css';
import '../../css/i/ihesg5bsf.css';
import '../../css/r/rfcsgtbnf.css';
import '../../css/s/sxq7-xbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x-sealbsy"/><path class="ihesg5bsf"/><path class="rfcsgtbnf"/><path class="sxq7-xbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-lightbulb" /></template>
