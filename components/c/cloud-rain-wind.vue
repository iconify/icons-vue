<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hax_fhbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hax_fhbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cloud-rain-wind" /></template>
