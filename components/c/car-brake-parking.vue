<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4b9-dbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4b9-dbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-brake-parking" /></template>
