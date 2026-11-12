<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za2uy5bzh.css';
import '../../css/w/wyv77qbzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="za2uy5bzh"/><path class="wyv77qbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:little-chat-light" /></template>
