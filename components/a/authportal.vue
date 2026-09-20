<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyt-wmt3x.css';
import '../../css/p/pmnep-p9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nyt-wmt3x"/><path class="pmnep-p9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:authportal" /></template>
