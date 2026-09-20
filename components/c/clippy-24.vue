<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw_haib9d.css';
import '../../css/d/deidzy81h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xw_haib9d"/><path class="deidzy81h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:clippy-24" /></template>
