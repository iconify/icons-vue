<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/a0poujb0g.css';
import '../../css/q/qyt7vo6ko.css';
import '../../css/c/cb8u71hty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="a0poujb0g"/><path class="qyt7vo6ko"/><path class="cb8u71hty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:camera-night-mode-01" /></template>
