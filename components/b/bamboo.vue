<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/maqgd4b9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="maqgd4b9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bamboo" /></template>
