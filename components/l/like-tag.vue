<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/v/vrht0cc8j.css';
import '../../css/e/eprq-zw1y.css';
import '../../css/s/ssl9qbxfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="vrht0cc8j"/><path class="eprq-zw1y"/><path class="ssl9qbxfx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:like-tag" /></template>
