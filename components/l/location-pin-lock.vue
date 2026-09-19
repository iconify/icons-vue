<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iax61qb5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iax61qb5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:location-pin-lock" /></template>
