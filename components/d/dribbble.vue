<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0vc2rmaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0vc2rmaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:dribbble" /></template>
