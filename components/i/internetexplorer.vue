<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4-zn3bud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":737,"height":729};
const content = `<path class="n4-zn3bud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:internetexplorer" /></template>
