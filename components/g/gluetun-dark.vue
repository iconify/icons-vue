<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh54a7btv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sh54a7btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gluetun-dark" /></template>
