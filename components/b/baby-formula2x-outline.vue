<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq-kee05t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bq-kee05t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:baby-formula2x-outline" /></template>
