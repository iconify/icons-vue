<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bis_l5bws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bis_l5bws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:costco-dark" /></template>
