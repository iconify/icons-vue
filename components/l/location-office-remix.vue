<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdzt5t5un.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pdzt5t5un"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:location-office-remix" /></template>
