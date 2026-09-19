<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo3c_0mes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xo3c_0mes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:grim-reaper" /></template>
