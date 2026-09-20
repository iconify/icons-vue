<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnrexiitu.css';
import '../../css/h/hzmc-yyoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnrexiitu"/><path class="hzmc-yyoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:locker-room-suitcase-key-bold" /></template>
