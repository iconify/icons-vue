<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1eecknay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1eecknay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-top-right-1" /></template>
