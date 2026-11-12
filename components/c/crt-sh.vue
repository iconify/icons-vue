<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa-vdingl.css';
import '../../css/s/sr532hb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qa-vdingl"/><path class="sr532hb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:crt-sh" /></template>
