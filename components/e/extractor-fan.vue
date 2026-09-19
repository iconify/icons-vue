<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqykk_bde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqykk_bde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:extractor-fan" /></template>
