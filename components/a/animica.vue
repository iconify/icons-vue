<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh11izblh.css';
import '../../css/w/w-y4u_k5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dh11izblh"/><path class="w-y4u_k5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:animica" /></template>
