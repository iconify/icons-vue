<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irf1ofbdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irf1ofbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:column-outline" /></template>
