<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uka2zbbdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uka2zbbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flask-empty-minus-outline" /></template>
