<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww9cxtb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ww9cxtb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bigcapital-light" /></template>
