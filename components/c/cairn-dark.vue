<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yawe7cbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yawe7cbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cairn-dark" /></template>
