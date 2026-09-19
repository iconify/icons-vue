<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3znfvbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o3znfvbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:cloudy-night-sharp" /></template>
