<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8p7xqizv.css';
import '../../css/i/ircx_pb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q8p7xqizv"/><path class="ircx_pb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:airplay" /></template>
