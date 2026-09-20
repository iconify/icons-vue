<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5s-b_bco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5s-b_bco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:blackberry" /></template>
