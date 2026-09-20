<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfz-8ubyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfz-8ubyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-check-variant" /></template>
