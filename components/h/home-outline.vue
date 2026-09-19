<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh1cy0bqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eh1cy0bqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:home-outline" /></template>
