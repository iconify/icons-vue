<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdu34r1wc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdu34r1wc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:airplane-alt-fill" /></template>
