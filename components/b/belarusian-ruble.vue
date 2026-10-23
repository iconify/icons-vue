<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbs-egr_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbs-egr_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:belarusian-ruble" /></template>
