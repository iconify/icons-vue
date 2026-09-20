<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktqu5ebjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktqu5ebjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:heart-3-fill" /></template>
