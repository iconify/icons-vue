<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g28hfjbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g28hfjbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:fluval-fx6" /></template>
