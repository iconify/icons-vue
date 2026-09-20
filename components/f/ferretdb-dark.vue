<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiaqa4bow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oiaqa4bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ferretdb-dark" /></template>
