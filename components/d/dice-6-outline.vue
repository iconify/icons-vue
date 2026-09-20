<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj3jorbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj3jorbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dice-6-outline" /></template>
