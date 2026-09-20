<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb_5-jbvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb_5-jbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bank-circle-outline" /></template>
