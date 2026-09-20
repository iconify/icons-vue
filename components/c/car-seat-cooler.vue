<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1na5ebkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1na5ebkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-seat-cooler" /></template>
