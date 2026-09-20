<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbrv5sbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mbrv5sbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:clean-broom-wipe-solid" /></template>
