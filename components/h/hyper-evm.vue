<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oal_t8bht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oal_t8bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:hyper-evm" /></template>
