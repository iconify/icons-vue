<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6f5zlbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n6f5zlbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:agregarr-light" /></template>
