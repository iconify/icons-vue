<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqlze7bpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqlze7bpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:box-minus" /></template>
