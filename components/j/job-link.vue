<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-_n6bcga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-_n6bcga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:job-link" /></template>
