<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf7me9nvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf7me9nvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:aeroplane-1" /></template>
