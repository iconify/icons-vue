<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_d-hsbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_d-hsbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chef-hat-fill-round" /></template>
