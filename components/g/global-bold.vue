<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7_h2kbdq.css';
import '../../css/h/hf83gzbzx.css';
import '../../css/s/sh7ni8bsi.css';
import '../../css/j/j3sofdbhr.css';
import '../../css/y/yfwp74xij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k7_h2kbdq"/><path class="hf83gzbzx"/><path class="sh7ni8bsi"/><path class="j3sofdbhr"/><path class="yfwp74xij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:global-bold" /></template>
