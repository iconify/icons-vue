<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er8_6gbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er8_6gbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:alert-octagon" /></template>
