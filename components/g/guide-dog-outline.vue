<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b783a2h0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b783a2h0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:guide-dog-outline" /></template>
