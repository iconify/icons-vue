<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui71xabtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ui71xabtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:loop-1-solid" /></template>
