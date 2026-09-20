<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bid-turbb.css';
import '../../css/t/t7741obxh.css';
import '../../css/c/cjo2vfb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bid-turbb"/><path class="t7741obxh"/><path class="cjo2vfb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bentopdf" /></template>
