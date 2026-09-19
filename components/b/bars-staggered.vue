<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw0emjb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gw0emjb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bars-staggered" /></template>
