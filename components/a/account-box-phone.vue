<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixw-142ey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":384};
const content = `<path class="ixw-142ey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:account-box-phone" /></template>
