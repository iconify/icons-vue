<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/z/z0ihehbja.css';
import '../../css/f/fwl6ucbbe.css';
import '../../css/b/bjxwieloe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="z0ihehbja"/><path class="fwl6ucbbe"/><path class="bjxwieloe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:camera-microphone-01" /></template>
