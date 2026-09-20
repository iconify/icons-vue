<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr08b61pk.css';
import '../../css/t/tjfi85b2h.css';
import '../../css/j/jyx3upbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="hr08b61pk"/><path class="tjfi85b2h"/><path class="jyx3upbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lollypop-music-player" /></template>
