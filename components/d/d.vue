<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jux0wcfxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jux0wcfxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:d" /></template>
