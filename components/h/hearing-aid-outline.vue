<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-ooy-buy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b-ooy-buy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:hearing-aid-outline" /></template>
