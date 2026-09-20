<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi3chnf-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bi3chnf-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-down-circle-line" /></template>
