<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj2firt2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sj2firt2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:label-variant" /></template>
