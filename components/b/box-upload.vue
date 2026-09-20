<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xs--b7q-p.css';
import '../../css/i/ic4_u_bgh.css';
import '../../css/z/ze0w8b34v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xs--b7q-p"/><path class="ic4_u_bgh"/><path class="ze0w8b34v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:box-upload" /></template>
