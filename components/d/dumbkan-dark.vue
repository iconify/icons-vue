<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5igd7btc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x5igd7btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dumbkan-dark" /></template>
