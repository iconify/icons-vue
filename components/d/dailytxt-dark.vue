<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh-v-bczu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dh-v-bczu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dailytxt-dark" /></template>
