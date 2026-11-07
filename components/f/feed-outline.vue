<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsv5t3btn.css';
import '../../css/u/uq14z1bmm.css';
import '../../css/q/qq35bdc4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hsv5t3btn"/><path class="uq14z1bmm"/><path clip-rule="evenodd" class="qq35bdc4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:feed-outline" /></template>
