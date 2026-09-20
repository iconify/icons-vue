<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itg833o_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itg833o_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:cloud-rain" /></template>
