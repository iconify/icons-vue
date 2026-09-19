<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir17xnytb.css';
import '../../css/b/b949_hboo.css';
import '../../css/t/tsjlmkb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer ir17xnytb"/><path class="b949_hboo duoicon-primary-layer"/><path class="duoicon-secondary-layer tsjlmkb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:app" /></template>
