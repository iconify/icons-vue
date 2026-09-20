<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8sj5ne3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="e8sj5ne3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:control-list-box" /></template>
