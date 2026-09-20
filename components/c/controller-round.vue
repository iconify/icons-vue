<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-37om-ac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-37om-ac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:controller-round" /></template>
