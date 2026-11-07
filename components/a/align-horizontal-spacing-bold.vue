<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co9si1b_r.css';
import '../../css/a/ansfvlgtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="co9si1b_r"/><path class="ansfvlgtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-horizontal-spacing-bold" /></template>
