<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asnfbccsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asnfbccsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:airplane-alt-02-filled" /></template>
