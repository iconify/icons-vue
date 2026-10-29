<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kngx7n1_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kngx7n1_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-up-z-a" /></template>
