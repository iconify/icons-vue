<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uehppmv_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uehppmv_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:homematic-ip-dark" /></template>
