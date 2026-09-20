<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufrkgtbsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufrkgtbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bed-single-outline" /></template>
