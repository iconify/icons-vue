<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua_-x4bud.css';
import '../../css/f/f2r653n8a.css';
import '../../css/q/qpob8mzln.css';
import '../../css/m/msjcjgj5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ua_-x4bud"/><path class="f2r653n8a"/><path class="qpob8mzln"/><path class="msjcjgj5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bxx" /></template>
