<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/digwz38ld.css';
import '../../css/n/nqbz-5bri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="digwz38ld secondary"/><path class="nqbz-5bri primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:club-duo" /></template>
