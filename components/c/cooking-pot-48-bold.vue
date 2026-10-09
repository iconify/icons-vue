<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6__lzt8k.css';
import '../../css/t/t50w30baf.css';
import '../../css/s/sfzihbf0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w6__lzt8k"/><path class="t50w30baf"/><path class="sfzihbf0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cooking-pot-48-bold" /></template>
