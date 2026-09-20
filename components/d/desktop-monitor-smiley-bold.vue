<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zoz24cbfm.css';
import '../../css/g/g5rkwvecy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zoz24cbfm"/><path class="g5rkwvecy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:desktop-monitor-smiley-bold" /></template>
