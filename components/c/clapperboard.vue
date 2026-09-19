<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpgm48bdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="bpgm48bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:clapperboard" /></template>
