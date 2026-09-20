<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmw-1gb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="mmw-1gb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-corner-up-left-keyboard-top-arrow-left-up" /></template>
