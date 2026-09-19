<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbwxpt-wq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tbwxpt-wq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:admin-network" /></template>
