<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuhqe4wvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="iuhqe4wvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:assignment-check" /></template>
