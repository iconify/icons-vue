<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl06tlnfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="sl06tlnfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:contraceptive-patch" /></template>
