<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e27cdebky.css';
import '../../css/y/yjuc4p29b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e27cdebky"/><path class="yjuc4p29b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:euro" /></template>
