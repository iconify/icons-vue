<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv796h8ch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fv796h8ch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:devices" /></template>
