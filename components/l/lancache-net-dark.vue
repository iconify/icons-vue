<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is_oe-rmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="is_oe-rmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lancache-net-dark" /></template>
