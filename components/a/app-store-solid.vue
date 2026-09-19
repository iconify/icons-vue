<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4wfp1bec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k4wfp1bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:app-store-solid" /></template>
