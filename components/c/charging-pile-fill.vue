<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6lajsw3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6lajsw3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:charging-pile-fill" /></template>
