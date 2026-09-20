<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vle0b1-wf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vle0b1-wf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:cogwheel-filled" /></template>
