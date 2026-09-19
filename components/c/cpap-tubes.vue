<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7b5tjbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="t7b5tjbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:cpap-tubes" /></template>
