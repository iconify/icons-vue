<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucyflh_rw.css';
import '../../css/h/hoos2y8tw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucyflh_rw"/><path class="hoos2y8tw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:bell-exclaimation" /></template>
