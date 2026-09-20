<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uylhht6xy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uylhht6xy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-edit" /></template>
