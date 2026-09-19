<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vza3v5bem.css';
import '../../css/c/cxpp0lxyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vza3v5bem"/><path class="cxpp0lxyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-show" /></template>
