<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctiym5e7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-0.5,"top":-0.5};
const content = `<path class="ctiym5e7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:flashlight-off" /></template>
