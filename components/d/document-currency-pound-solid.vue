<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohbsmwbpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ohbsmwbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-currency-pound-solid" /></template>
