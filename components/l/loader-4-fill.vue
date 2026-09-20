<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h524gymsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h524gymsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:loader-4-fill" /></template>
