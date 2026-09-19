<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbiz79bon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jbiz79bon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:assembly-hitachi" /></template>
