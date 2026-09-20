<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tch1x7qyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="tch1x7qyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-button-left-arrow-keyboard-left" /></template>
