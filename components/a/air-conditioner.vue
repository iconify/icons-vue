<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v55azh8hv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v55azh8hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:air-conditioner" /></template>
