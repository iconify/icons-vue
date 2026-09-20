<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3rx1sb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3rx1sb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:book-medical" /></template>
