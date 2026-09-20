<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd-w0-blg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qd-w0-blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:clipboard-check" /></template>
