<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym2f5wksi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ym2f5wksi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:alfa1" /></template>
