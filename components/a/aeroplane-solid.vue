<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv5z_obdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv5z_obdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:aeroplane-solid" /></template>
