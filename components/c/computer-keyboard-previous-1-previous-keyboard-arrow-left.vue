<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcg4c_nrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="wcg4c_nrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:computer-keyboard-previous-1-previous-keyboard-arrow-left" /></template>
