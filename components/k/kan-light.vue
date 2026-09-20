<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sisk_ebgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sisk_ebgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kan-light" /></template>
