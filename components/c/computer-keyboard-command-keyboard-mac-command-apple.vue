<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u89zr7b9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="u89zr7b9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:computer-keyboard-command-keyboard-mac-command-apple" /></template>
