<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_cmk7-2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k_cmk7-2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:bill-dollar-1-solid" /></template>
