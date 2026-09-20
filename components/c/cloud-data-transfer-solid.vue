<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1433jbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q1433jbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:cloud-data-transfer-solid" /></template>
