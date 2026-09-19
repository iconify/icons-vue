<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt2ibvuil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt2ibvuil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:lock-open" /></template>
