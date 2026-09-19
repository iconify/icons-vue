<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9jjl7gyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9jjl7gyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:grid-alt" /></template>
