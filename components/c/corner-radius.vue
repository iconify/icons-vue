<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7b_59b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7b_59b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:corner-radius" /></template>
