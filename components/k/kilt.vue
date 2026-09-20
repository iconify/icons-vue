<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z82ysocfk.css';
import '../../css/h/h0h1ev4io.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z82ysocfk"/><path class="h0h1ev4io"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:kilt" /></template>
