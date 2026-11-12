<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj4hvkb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yj4hvkb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amazon-web-services-dark" /></template>
