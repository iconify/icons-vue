<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-h8ahbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p-h8ahbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:m-t-bank" /></template>
