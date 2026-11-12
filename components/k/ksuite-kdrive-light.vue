<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqb529s1o.css';
import '../../css/z/zrjwygnwg.css';
import '../../css/q/qt8z-bb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qqb529s1o"/><path class="zrjwygnwg"/><path class="qt8z-bb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-kdrive-light" /></template>
