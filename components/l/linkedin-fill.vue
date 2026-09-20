<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oizdzrb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oizdzrb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:linkedin-fill" /></template>
