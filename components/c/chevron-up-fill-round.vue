<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltlsmruzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltlsmruzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-up-fill-round" /></template>
