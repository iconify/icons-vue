<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lipib6elo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lipib6elo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:download-square-solid" /></template>
