<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b35q_0bvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b35q_0bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:i-exam-multiple-choice" /></template>
