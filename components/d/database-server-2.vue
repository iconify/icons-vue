<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muy2xg7rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muy2xg7rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:database-server-2" /></template>
