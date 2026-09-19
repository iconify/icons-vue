<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc459gpon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zc459gpon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:liver-alt-outline" /></template>
