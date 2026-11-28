<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tun7kpbmr.css';
import '../../css/a/a2uaf5emu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary tun7kpbmr"/><path class="a2uaf5emu primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:folder-duo" /></template>
