<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uek5jjtrg.css';
import '../../css/p/psb-p714j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uek5jjtrg"/><path class="psb-p714j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:circus-elephant-bold" /></template>
