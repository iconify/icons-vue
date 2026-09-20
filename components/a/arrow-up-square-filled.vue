<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0p8aac4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0p8aac4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-up-square-filled" /></template>
