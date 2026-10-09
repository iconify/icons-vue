<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1mcems0k.css';
import '../../css/p/pbmaa1b1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l1mcems0k"/><path class="pbmaa1b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-droplet-20-bold" /></template>
