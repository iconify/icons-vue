<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivu-dmb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ivu-dmb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:achievement" /></template>
