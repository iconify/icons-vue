<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u08u5qbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u08u5qbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dots-3x2-16-solid" /></template>
