<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlds2mbdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlds2mbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bell-minus" /></template>
