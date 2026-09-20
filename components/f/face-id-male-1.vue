<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkr_3bbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dkr_3bbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:face-id-male-1" /></template>
