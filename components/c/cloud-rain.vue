<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfrb8nbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfrb8nbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cloud-rain" /></template>
