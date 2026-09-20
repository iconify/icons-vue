<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdezvif_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zdezvif_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:car-taxi-1-remix" /></template>
