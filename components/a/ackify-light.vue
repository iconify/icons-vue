<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg0_fpbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xg0_fpbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ackify-light" /></template>
