<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtca2iexn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtca2iexn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-dw-p2" /></template>
