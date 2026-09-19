<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvoxb-ghc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvoxb-ghc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:layer-send-backward" /></template>
