<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfq-i7j7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":384};
const content = `<path class="vfq-i7j7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:label-alt" /></template>
