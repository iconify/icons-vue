<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2qn1cbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2qn1cbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-card-details" /></template>
