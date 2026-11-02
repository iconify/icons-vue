<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh42j-28c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vh42j-28c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-curve-down-right" /></template>
