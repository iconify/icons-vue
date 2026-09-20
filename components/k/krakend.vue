<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyum4tzso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wyum4tzso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:krakend" /></template>
