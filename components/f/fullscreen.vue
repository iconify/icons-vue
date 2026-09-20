<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0ohn_fmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q0ohn_fmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:fullscreen" /></template>
