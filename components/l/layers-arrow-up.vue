<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu02f0bmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bu02f0bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:layers-arrow-up" /></template>
