<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be0vdpbnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="be0vdpbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:hardware-camera" /></template>
