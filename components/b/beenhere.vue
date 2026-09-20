<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urm4i36ho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urm4i36ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:beenhere" /></template>
