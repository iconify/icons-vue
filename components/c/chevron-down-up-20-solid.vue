<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vybyybb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vybyybb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:chevron-down-up-20-solid" /></template>
