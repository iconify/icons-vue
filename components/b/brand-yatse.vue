<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz3qru_7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz3qru_7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-yatse" /></template>
