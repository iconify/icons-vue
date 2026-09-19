<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivhbr1sli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivhbr1sli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:border-all-01" /></template>
