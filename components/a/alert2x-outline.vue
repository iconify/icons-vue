<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci9od1bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ci9od1bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:alert2x-outline" /></template>
