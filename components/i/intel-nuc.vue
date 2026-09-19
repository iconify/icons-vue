<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee7saccos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee7saccos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:intel-nuc" /></template>
