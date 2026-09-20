<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6dbjw9zi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="x6dbjw9zi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:chevron-down" /></template>
