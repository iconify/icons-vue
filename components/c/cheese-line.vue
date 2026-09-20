<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihpfuxbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihpfuxbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:cheese-line" /></template>
