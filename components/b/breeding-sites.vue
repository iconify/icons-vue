<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq-0zhbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bq-0zhbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:breeding-sites" /></template>
