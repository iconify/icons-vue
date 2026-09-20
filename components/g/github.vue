<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg96njcks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fg96njcks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:github" /></template>
