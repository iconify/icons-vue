<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3mbkdb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p3mbkdb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:h4-20-solid" /></template>
