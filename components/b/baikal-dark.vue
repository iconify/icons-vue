<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkggutxno.css';
import '../../css/n/nvqrqlbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dkggutxno"/><path class="nvqrqlbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:baikal-dark" /></template>
