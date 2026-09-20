<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go7qv8fna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go7qv8fna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-turbocharger" /></template>
