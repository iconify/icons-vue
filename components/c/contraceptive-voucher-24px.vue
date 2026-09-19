<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5a4ewb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c5a4ewb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:contraceptive-voucher-24px" /></template>
