<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va9rngbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="va9rngbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:dice-d4-solid" /></template>
