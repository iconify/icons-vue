<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu0s6g77s.css';
import '../../css/o/ohftsia-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu0s6g77s wm-a"/><path class="ohftsia-f wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:fast-forward" /></template>
