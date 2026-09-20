<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvuiclbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvuiclbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:fire-minimalistic-broken" /></template>
