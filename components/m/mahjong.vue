<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhqbhisui.css';
import '../../css/j/jvlxhcclc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nhqbhisui"/><path class="jvlxhcclc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:mahjong" /></template>
