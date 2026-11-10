<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lax5n35xm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lax5n35xm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:cellular-network-lte" /></template>
