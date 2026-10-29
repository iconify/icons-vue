<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khp8l0vbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khp8l0vbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:factory" /></template>
