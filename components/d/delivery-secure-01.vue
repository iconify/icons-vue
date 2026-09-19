<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4t3_bbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4t3_bbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:delivery-secure-01" /></template>
