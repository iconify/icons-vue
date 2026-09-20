<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlcmmrb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nlcmmrb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dell-dark" /></template>
