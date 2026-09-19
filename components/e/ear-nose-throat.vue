<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph9ekmbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ph9ekmbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ear-nose-throat" /></template>
