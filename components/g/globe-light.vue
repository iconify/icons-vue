<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp2t19eno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lp2t19eno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:globe-light" /></template>
