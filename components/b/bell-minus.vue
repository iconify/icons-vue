<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnhz1hbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnhz1hbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:bell-minus" /></template>
