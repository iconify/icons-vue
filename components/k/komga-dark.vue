<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pof-r7bip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pof-r7bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:komga-dark" /></template>
