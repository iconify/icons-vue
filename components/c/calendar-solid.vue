<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5h48mmha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5h48mmha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:calendar-solid" /></template>
