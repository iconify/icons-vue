<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utfj6q1tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utfj6q1tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cloud-alert-solid" /></template>
