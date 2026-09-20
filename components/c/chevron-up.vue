<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns9w8983n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ns9w8983n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:chevron-up" /></template>
