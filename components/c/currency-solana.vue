<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsxp_0bcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsxp_0bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-solana" /></template>
