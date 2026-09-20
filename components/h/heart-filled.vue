<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpcwrbc7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="vpcwrbc7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:heart-filled" /></template>
