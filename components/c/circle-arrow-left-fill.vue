<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzri7tbxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzri7tbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-arrow-left-fill" /></template>
