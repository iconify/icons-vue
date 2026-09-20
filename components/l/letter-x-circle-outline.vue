<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/samu3ccav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="samu3ccav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-x-circle-outline" /></template>
