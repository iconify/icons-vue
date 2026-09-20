<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nczzpqi_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="nczzpqi_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:chevron-left-right-20-solid" /></template>
