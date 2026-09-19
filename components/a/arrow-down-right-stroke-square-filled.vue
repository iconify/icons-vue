<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgpv_eb_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgpv_eb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-down-right-stroke-square-filled" /></template>
