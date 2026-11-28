<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3vbcq4wi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3vbcq4wi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:flashlight-check" /></template>
