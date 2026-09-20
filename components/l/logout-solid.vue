<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9s052bms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9s052bms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:logout-solid" /></template>
