<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox7ar-sbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox7ar-sbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:elavon" /></template>
