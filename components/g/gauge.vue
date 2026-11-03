<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utovdcc_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utovdcc_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:gauge" /></template>
