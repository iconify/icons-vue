<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikjv1wknt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ikjv1wknt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:alarm-clock" /></template>
