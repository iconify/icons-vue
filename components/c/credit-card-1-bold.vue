<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfl8oab7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfl8oab7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:credit-card-1-bold" /></template>
