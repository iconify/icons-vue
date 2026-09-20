<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr4wvub4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mr4wvub4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:compass-big-bold" /></template>
