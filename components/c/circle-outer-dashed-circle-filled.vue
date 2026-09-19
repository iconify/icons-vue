<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krwo12_et.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krwo12_et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:circle-outer-dashed-circle-filled" /></template>
