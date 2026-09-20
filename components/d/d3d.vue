<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-w3vmb5c.css';
import '../../css/m/m97pomy2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-w3vmb5c"/><path clip-rule="evenodd" class="m97pomy2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:d3d" /></template>
