<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7eff_agy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7eff_agy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-autofit-right" /></template>
