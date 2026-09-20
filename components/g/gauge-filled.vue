<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4ov4gbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o4ov4gbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:gauge-filled" /></template>
