<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8ejirjck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="j8ejirjck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:baby-0203m-outline" /></template>
