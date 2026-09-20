<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce5k8p2hr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ce5k8p2hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:home-4-fill" /></template>
