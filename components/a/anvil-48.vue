<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibd5-t-ac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ibd5-t-ac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:anvil-48" /></template>
