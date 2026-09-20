<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tguvsp97z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tguvsp97z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ironmount" /></template>
