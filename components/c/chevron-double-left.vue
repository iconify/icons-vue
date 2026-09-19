<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhnrx_bfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhnrx_bfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chevron-double-left" /></template>
