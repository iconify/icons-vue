<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq9e_tbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq9e_tbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:angular" /></template>
