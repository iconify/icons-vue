<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onovt9qwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onovt9qwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:air-presure" /></template>
