<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls29xvmdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ls29xvmdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:circle-small-outline" /></template>
