<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx66pva8x.css';
import '../../css/l/l67st8b5a.css';
import '../../css/s/s_a69j5sy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx66pva8x wm-k"/><path class="l67st8b5a wm-a"/><path class="s_a69j5sy wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:image" /></template>
