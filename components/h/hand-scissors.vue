<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfxii2bgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bfxii2bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hand-scissors" /></template>
