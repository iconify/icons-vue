<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi369eb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="xi369eb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:button-pause-2" /></template>
