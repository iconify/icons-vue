<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n11x2ztin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n11x2ztin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:external-link" /></template>
