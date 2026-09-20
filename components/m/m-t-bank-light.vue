<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vawi9eb7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vawi9eb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:m-t-bank-light" /></template>
