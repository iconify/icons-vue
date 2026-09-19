<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyr57ub8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qyr57ub8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:magic-stick" /></template>
