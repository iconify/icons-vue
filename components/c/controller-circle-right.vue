<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e77d1dtiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e77d1dtiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:controller-circle-right" /></template>
