<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqs_ijbso.css';
import '../../css/g/g1vnq256e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xqs_ijbso"/><path class="g1vnq256e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:fantom" /></template>
