<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/poa381bhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="poa381bhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cart-x-filled" /></template>
