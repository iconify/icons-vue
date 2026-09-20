<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aseyl3-sf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="aseyl3-sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-down-arrow-down-keyboard" /></template>
