<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltns5k4cl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltns5k4cl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bank-card-line" /></template>
