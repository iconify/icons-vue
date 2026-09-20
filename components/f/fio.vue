<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trwtybczh.css';
import '../../css/s/s39r46bkt.css';
import '../../css/h/hoofw7boh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trwtybczh"/><path class="s39r46bkt"/><path class="hoofw7boh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:fio" /></template>
