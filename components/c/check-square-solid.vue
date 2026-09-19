<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlu8tx4gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hlu8tx4gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:check-square-solid" /></template>
