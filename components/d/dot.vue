<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx6wvua0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx6wvua0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:dot" /></template>
