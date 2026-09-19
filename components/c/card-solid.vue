<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktk1idz1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ktk1idz1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:card-solid" /></template>
