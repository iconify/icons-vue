<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z17k1cbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z17k1cbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-e-circle-outline" /></template>
