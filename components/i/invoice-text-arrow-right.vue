<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haw7i_f8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="haw7i_f8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-text-arrow-right" /></template>
