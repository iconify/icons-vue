<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8pt4eu3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m8pt4eu3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:lightbulb-off" /></template>
