<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkx-nwsxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkx-nwsxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:error-502" /></template>
