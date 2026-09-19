<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nig1hzzvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nig1hzzvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:cast" /></template>
