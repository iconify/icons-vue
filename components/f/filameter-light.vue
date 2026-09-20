<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj7ba9y9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vj7ba9y9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:filameter-light" /></template>
