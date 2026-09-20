<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8rru2b7i.css';
import '../../css/d/dwn288bus.css';
import '../../css/g/gddrajlcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p8rru2b7i"/><path class="dwn288bus"/><path class="gddrajlcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:logo-twitch-2" /></template>
