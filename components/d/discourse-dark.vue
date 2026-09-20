<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3tiyj8sa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l3tiyj8sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:discourse-dark" /></template>
