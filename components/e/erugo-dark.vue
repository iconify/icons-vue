<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvje_n8dl.css';
import '../../css/x/x662ljhor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dvje_n8dl"/><path class="x662ljhor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:erugo-dark" /></template>
