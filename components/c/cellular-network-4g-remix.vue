<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzdrmbgrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pzdrmbgrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cellular-network-4g-remix" /></template>
