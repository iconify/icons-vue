<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/didt0l-fl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="didt0l-fl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amazon-web-services-light" /></template>
