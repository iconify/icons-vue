<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adszbn4wz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adszbn4wz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:first-aid-round" /></template>
