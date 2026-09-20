<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nelr1hbfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nelr1hbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:layout-4-fill" /></template>
