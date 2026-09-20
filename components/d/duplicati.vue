<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvi92ybru.css';
import '../../css/k/k9wv4hbjg.css';
import '../../css/f/fcv7rpbbv.css';
import '../../css/z/z-rjlmbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vvi92ybru"/><path class="k9wv4hbjg"/><path class="fcv7rpbbv"/><path class="z-rjlmbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:duplicati" /></template>
