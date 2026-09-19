<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2cnbnb2l.css';
import '../../css/z/zbeas57fc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y2cnbnb2l"/><path class="zbeas57fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:decreasefontsize" /></template>
