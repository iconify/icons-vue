<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfydo-uvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="nfydo-uvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:hocho-small-filled" /></template>
