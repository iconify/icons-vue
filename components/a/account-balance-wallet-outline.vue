<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uggz1wboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uggz1wboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-balance-wallet-outline" /></template>
