<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v41b5ferv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v41b5ferv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-spacehey" /></template>
