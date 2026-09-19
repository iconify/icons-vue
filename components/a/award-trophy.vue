<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k813c362p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="k813c362p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:award-trophy" /></template>
