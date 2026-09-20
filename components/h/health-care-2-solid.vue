<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih27f4boy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ih27f4boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:health-care-2-solid" /></template>
