<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmnb66mry.css';
import '../../css/z/z46nhhf2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lmnb66mry"/><path class="z46nhhf2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bolt-diy" /></template>
