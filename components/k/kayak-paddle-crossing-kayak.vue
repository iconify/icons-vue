<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb3l59rwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nb3l59rwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:kayak-paddle-crossing-kayak" /></template>
