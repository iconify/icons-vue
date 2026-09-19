<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw83j6bta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw83j6bta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:credit-card" /></template>
