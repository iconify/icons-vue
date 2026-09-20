<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed6msyqpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ed6msyqpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ceph-light" /></template>
