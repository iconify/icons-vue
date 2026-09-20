<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtpb7vbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtpb7vbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoji-tongue" /></template>
