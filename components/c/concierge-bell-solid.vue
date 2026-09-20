<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdtdpfb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jdtdpfb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:concierge-bell-solid" /></template>
