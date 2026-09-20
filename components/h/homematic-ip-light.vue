<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eut-2bbay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eut-2bbay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:homematic-ip-light" /></template>
