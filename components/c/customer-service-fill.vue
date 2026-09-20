<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io8fdue6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io8fdue6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:customer-service-fill" /></template>
