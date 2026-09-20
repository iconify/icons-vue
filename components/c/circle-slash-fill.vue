<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to1fr9hry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="to1fr9hry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-slash-fill" /></template>
