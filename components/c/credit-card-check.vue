<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iba52wwer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iba52wwer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:credit-card-check" /></template>
