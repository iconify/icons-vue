<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywm2orvft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="ywm2orvft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:dns" /></template>
