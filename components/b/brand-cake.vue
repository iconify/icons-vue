<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-4-x7bhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-4-x7bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-cake" /></template>
