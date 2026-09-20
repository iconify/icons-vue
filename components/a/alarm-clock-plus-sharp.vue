<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-mmafbfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-mmafbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:alarm-clock-plus-sharp" /></template>
