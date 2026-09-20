<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxi_nimou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxi_nimou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ipfs" /></template>
