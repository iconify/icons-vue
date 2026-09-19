<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3wp4wbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3wp4wbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:health-alt-24px" /></template>
