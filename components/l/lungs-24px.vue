<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm1j0bb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cm1j0bb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:lungs-24px" /></template>
