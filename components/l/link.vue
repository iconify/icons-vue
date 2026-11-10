<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt1rr2bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt1rr2bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:link" /></template>
