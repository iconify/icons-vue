<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5fuxbhra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x5fuxbhra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-badge-fill-20" /></template>
