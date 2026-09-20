<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3to5ubug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3to5ubug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:address-marker-outline" /></template>
