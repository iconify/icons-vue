<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjqz-ibde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kjqz-ibde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ars-technica-dark" /></template>
