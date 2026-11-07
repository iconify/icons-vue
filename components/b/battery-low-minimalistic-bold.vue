<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr-6t8b6g.css';
import '../../css/q/qfc_s602x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zr-6t8b6g"/><path class="qfc_s602x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:battery-low-minimalistic-bold" /></template>
