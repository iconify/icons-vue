<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii-15nbsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ii-15nbsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:add-circle-fill" /></template>
