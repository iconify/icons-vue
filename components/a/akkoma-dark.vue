<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smgz1ib2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="smgz1ib2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:akkoma-dark" /></template>
