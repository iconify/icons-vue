<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxqac0bmw.css';
import '../../css/j/j2ghpnx_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxqac0bmw"/><circle class="j2ghpnx_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:atom" /></template>
