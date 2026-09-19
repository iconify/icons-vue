<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp3507b3q.css';
import '../../css/m/mef_eabep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp3507b3q"/><path class="mef_eabep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-building-house" /></template>
