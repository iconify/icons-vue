<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hadc8s2xv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hadc8s2xv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:carton" /></template>
