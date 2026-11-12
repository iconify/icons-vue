<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjeg35jty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pjeg35jty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fluxer-light" /></template>
