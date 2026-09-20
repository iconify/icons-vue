<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kepsv4b0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kepsv4b0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:emotion-add-line" /></template>
