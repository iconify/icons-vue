<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggaa8vbqw.css';
import '../../css/d/dgyyfkyiu.css';
import '../../css/l/l97nb-quh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggaa8vbqw"/><path class="dgyyfkyiu"/><circle class="l97nb-quh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-wifi" /></template>
