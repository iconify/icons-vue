<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_swpv-ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_swpv-ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-sync-outline" /></template>
