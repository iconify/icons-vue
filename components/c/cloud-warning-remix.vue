<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbw8hbcnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vbw8hbcnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cloud-warning-remix" /></template>
