<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u59agyaoz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u59agyaoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:magic-line" /></template>
