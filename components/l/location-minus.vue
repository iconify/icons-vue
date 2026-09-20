<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inb6nib5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inb6nib5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:location-minus" /></template>
