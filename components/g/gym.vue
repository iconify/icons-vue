<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klt4mrzdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="klt4mrzdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:gym" /></template>
