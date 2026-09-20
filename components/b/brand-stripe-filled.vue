<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qoiouibpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qoiouibpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-stripe-filled" /></template>
