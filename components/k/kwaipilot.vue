<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtr80hbkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rtr80hbkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:kwaipilot" /></template>
