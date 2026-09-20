<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mre13ubyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mre13ubyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cart-discount" /></template>
