<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/woup13bgg.css';
import '../../css/s/scdda8sqr.css';
import '../../css/q/qt8553dci.css';
import '../../css/d/dkcwfxbnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="woup13bgg"/><path class="scdda8sqr"/><path class="qt8553dci"/><path class="dkcwfxbnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:fish" /></template>
