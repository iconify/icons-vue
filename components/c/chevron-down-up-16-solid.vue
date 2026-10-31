<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_m51orpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x_m51orpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:chevron-down-up-16-solid" /></template>
