<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj1be0vek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mj1be0vek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:alert-square-rounded-off" /></template>
