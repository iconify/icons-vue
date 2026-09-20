<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chzugt96m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chzugt96m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:eqx" /></template>
