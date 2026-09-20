<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q60h5cboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q60h5cboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cairn-light" /></template>
