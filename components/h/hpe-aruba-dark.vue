<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwxc7_b3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nwxc7_b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hpe-aruba-dark" /></template>
