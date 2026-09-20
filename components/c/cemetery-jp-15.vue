<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0x2i849g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q0x2i849g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:cemetery-jp-15" /></template>
