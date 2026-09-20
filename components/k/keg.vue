<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz_m-jh8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dz_m-jh8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:keg" /></template>
