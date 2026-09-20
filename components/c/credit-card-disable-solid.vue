<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kclp8acnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kclp8acnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:credit-card-disable-solid" /></template>
