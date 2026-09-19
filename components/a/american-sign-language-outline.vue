<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwjv8hipc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zwjv8hipc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:american-sign-language-outline" /></template>
