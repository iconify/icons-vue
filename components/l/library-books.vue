<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etjoxb8eh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etjoxb8eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:library-books" /></template>
