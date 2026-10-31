<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6l3pw3yy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6l3pw3yy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-arrow-up-round" /></template>
