<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6x_aab7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6x_aab7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:link-break-filled" /></template>
