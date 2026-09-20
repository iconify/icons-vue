<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw_2ctbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gw_2ctbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kavita-dark" /></template>
