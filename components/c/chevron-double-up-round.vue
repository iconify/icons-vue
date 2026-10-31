<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mti2apb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mti2apb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-double-up-round" /></template>
