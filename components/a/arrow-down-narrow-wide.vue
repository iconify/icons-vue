<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka267ac_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ka267ac_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-down-narrow-wide" /></template>
