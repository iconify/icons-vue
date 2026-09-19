<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4llb9ccr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="j4llb9ccr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:cone-test-on-walls" /></template>
