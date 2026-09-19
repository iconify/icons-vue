<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e22ort1_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e22ort1_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:briefcase-alt" /></template>
