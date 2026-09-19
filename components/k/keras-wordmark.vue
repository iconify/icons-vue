<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_flxzbbv.css';
import '../../css/c/c4k71-bhq.css';
import '../../css/i/iovi16bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="q_flxzbbv"/><path class="c4k71-bhq"/><path class="iovi16bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:keras-wordmark" /></template>
