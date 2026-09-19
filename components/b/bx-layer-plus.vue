<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmzy6u1qm.css';
import '../../css/i/iya8o4byy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmzy6u1qm"/><path class="iya8o4byy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-layer-plus" /></template>
