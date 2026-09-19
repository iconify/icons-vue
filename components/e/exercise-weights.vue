<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gib52b7lk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gib52b7lk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:exercise-weights" /></template>
