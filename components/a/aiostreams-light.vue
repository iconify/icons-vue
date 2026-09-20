<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5_huo6_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k5_huo6_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:aiostreams-light" /></template>
