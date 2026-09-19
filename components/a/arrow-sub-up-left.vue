<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzxrv2nrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzxrv2nrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-sub-up-left" /></template>
