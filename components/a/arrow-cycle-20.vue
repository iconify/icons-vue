<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e74qa5bzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e74qa5bzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-cycle-20" /></template>
