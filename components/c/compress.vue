<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpe_9bcmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpe_9bcmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:compress" /></template>
