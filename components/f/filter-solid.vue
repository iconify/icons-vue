<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gngvdr8bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gngvdr8bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:filter-solid" /></template>
