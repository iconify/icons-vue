<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snt3n6ezt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snt3n6ezt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-brake-retarder" /></template>
