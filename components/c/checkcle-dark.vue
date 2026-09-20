<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw8ww4nck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fw8ww4nck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:checkcle-dark" /></template>
