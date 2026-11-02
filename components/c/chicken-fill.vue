<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scooq2b_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scooq2b_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chicken-fill" /></template>
