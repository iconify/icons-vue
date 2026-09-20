<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cikj799ze.css';
import '../../css/j/ji6cdtapd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cikj799ze"/><path clip-rule="evenodd" class="ji6cdtapd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:let" /></template>
