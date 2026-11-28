<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhm3bqbpv.css';
import '../../css/r/rc5cwfboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary uhm3bqbpv"/><path class="primary rc5cwfboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:github-duo" /></template>
