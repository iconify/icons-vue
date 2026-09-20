<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa3_oub9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fa3_oub9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bible-gateway-dark" /></template>
