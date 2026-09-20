<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evt2zjc8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evt2zjc8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bank-fill" /></template>
