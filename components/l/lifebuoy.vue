<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwnw9_bsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwnw9_bsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:lifebuoy" /></template>
