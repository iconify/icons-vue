<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db-naac_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="db-naac_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:fingerprint-2-flat" /></template>
