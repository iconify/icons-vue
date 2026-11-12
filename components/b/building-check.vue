<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_u2cyq9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_u2cyq9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:building-check" /></template>
