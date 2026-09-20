<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufw4fv8xu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ufw4fv8xu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:circle-20-solid" /></template>
