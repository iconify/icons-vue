<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eobs_dz0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eobs_dz0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:cloud-off" /></template>
