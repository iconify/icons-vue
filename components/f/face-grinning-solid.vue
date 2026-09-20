<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi4wy4h2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xi4wy4h2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:face-grinning-solid" /></template>
