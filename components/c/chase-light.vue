<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tce8ar49c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tce8ar49c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chase-light" /></template>
