<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv8unqoqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv8unqoqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:heat-pump-outline" /></template>
