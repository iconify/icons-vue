<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0dij1bjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="r0dij1bjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:handshake-20-solid" /></template>
