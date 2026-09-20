<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rypl5_97b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rypl5_97b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hpe-aruba" /></template>
