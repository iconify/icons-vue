<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmi07_fwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmi07_fwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:ethernet-port" /></template>
