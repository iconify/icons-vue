<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dctws6vgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dctws6vgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:button-next-remix" /></template>
