<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa1hqydsf.css';
import '../../css/u/uy-sggl9k.css';
import '../../css/r/rers1paxa.css';
import '../../css/a/aui-jmtcx.css';
import '../../css/u/uv4oycn3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fa1hqydsf"/><path class="uy-sggl9k"/><path class="rers1paxa"/><path class="aui-jmtcx"/><path class="uv4oycn3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gamepad-outline" /></template>
