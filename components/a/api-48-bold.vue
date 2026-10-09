<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqu5shbcg.css';
import '../../css/x/x_zkkvfvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rqu5shbcg"/><path class="x_zkkvfvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:api-48-bold" /></template>
