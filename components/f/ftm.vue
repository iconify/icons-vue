<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6pwpnejz.css';
import '../../css/w/wgjjxmigs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m6pwpnejz"/><path class="wgjjxmigs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ftm" /></template>
