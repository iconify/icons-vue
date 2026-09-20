<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz9fp19zf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mz9fp19zf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:checkcle" /></template>
