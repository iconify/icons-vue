<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j88ll_bcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="j88ll_bcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blood-bag-negative" /></template>
