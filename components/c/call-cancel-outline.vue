<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux5jk213g.css';
import '../../css/l/l8p24vbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ux5jk213g"/><path class="l8p24vbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:call-cancel-outline" /></template>
