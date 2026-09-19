<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyyd_bcid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyyd_bcid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:laundry-2" /></template>
