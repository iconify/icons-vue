<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krjyr2bou.css';
import '../../css/e/e9nqe7b2h.css';
import '../../css/k/k8ixw89dy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="krjyr2bou"/><path class="e9nqe7b2h"/><path class="k8ixw89dy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:articles-rtl" /></template>
