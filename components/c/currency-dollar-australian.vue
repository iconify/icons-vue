<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-9517b_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-9517b_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-dollar-australian" /></template>
