<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y07wqubtc.css';
import '../../css/w/wckr9kb1z.css';
import '../../css/h/hd5qmml4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="y07wqubtc"/><path class="wckr9kb1z"/><path class="hd5qmml4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-album" /></template>
