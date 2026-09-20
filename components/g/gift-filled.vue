<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tot-1lbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tot-1lbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:gift-filled" /></template>
