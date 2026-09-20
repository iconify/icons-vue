<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs39h7bpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs39h7bpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:collapse-all-outline" /></template>
