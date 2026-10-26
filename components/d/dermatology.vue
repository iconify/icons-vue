<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk4-6obph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lk4-6obph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:dermatology" /></template>
