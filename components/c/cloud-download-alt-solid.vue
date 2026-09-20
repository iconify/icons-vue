<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l73x2db2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l73x2db2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cloud-download-alt-solid" /></template>
