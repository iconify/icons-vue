<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7q0o6bdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7q0o6bdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:letter-r" /></template>
