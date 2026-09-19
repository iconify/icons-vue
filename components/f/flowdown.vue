<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_xpt5bbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":833};
const content = `<path class="e_xpt5bbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:flowdown" /></template>
